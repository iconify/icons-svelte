<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v4b39in.css';
import '../../css/x/x8-usg97v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="c9v4b39in"/><path clip-rule="evenodd" class="x8-usg97v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search-plus" {...props}></Icon>
