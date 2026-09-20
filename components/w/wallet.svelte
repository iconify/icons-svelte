<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8egmnwzy.css';
import '../../css/c/civwcmd-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8egmnwzy"/><path class="civwcmd-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:wallet" {...props}></Icon>
