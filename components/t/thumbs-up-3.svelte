<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9svxzerl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9svxzerl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thumbs-up-3" {...props}></Icon>
