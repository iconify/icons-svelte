<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9qwmvb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9qwmvb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-vimeo" {...props}></Icon>
