<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2g407byi.css';
import '../../css/m/m7wldfb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2g407byi"/><path class="m7wldfb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unread-24" {...props}></Icon>
