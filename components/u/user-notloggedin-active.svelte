<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id-0tgb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id-0tgb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:user-notloggedin-active" {...props}></Icon>
