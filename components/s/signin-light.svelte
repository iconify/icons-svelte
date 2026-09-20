<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8tws73yk.css';
import '../../css/w/wn5ynabza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8tws73yk"/><path class="wn5ynabza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signin-light" {...props}></Icon>
