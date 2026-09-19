<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trio7-bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":527,"height":754};
const content = `<path class="trio7-bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:u-upper-case" {...props}></Icon>
