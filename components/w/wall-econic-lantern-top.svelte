<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-4s1ubmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-4s1ubmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-econic-lantern-top" {...props}></Icon>
