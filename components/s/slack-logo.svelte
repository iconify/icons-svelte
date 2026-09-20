<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vulvr1biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vulvr1biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slack-logo" {...props}></Icon>
