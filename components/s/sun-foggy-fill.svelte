<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/furb690ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="furb690ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sun-foggy-fill" {...props}></Icon>
