<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5nr5ubw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5nr5ubw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-stop" {...props}></Icon>
