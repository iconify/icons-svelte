<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl70btbxk.css';
import '../../css/a/ax074xbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl70btbxk"/><path class="ax074xbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:wand-duotone" {...props}></Icon>
