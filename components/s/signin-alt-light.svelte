<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjckms-gm.css';
import '../../css/w/wpmkoacem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjckms-gm"/><path class="wpmkoacem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signin-alt-light" {...props}></Icon>
