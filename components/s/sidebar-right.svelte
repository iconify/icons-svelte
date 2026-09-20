<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozuui3bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozuui3bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-right" {...props}></Icon>
