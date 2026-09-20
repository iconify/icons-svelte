<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk150c_4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nk150c_4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:shield" {...props}></Icon>
