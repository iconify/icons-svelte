<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aags1jb7a.css';
import '../../css/f/fve51_hdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aags1jb7a"/><path class="fve51_hdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:shopping-bag" {...props}></Icon>
