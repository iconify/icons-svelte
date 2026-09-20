<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0-m9noxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0-m9noxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tpad" {...props}></Icon>
