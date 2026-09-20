<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xshb9nbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xshb9nbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-user-fill" {...props}></Icon>
