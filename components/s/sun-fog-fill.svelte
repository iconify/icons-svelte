<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up9h4bj1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up9h4bj1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-fog-fill" {...props}></Icon>
