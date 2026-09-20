<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkjo3ifcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="wkjo3ifcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:svelte" {...props}></Icon>
