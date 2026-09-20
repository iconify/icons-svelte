<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp7vij--s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bp7vij--s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:steam-logo-block" {...props}></Icon>
