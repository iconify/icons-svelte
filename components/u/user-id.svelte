<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1x756bcr.css';
import '../../css/a/av7mo7pep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1x756bcr"/><path class="av7mo7pep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-id" {...props}></Icon>
