<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plkxy1bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plkxy1bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-heart-light" {...props}></Icon>
