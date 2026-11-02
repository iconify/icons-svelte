<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjux9zbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjux9zbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-cloudy-fill" {...props}></Icon>
