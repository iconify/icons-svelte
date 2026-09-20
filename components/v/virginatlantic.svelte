<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmyj_bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmyj_bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:virginatlantic" {...props}></Icon>
