<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7orre6ne.css';
import '../../css/n/nk_c-zevr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7orre6ne"/><path class="nk_c-zevr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-circle" {...props}></Icon>
