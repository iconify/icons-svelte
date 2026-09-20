<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnk0yztxu.css';
import '../../css/x/x8-usg97v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="bnk0yztxu"/><path clip-rule="evenodd" class="x8-usg97v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search-text" {...props}></Icon>
