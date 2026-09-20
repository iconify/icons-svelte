<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6j1nk9mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h6j1nk9mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-record-outline" {...props}></Icon>
