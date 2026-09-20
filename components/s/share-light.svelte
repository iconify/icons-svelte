<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6rlxbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp6rlxbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:share-light" {...props}></Icon>
