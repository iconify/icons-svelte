<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9vxdh5en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o9vxdh5en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search-minus" {...props}></Icon>
