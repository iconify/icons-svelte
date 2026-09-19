<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt8bflbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wt8bflbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:zotero-square" {...props}></Icon>
