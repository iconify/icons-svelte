<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utj6gpbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utj6gpbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:toggle-fill" {...props}></Icon>
