<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avywr9bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avywr9bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-switch-module" {...props}></Icon>
