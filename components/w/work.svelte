<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj1d7bwxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wj1d7bwxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work" {...props}></Icon>
