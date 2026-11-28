<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsppwy8tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsppwy8tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:watering-can-clock" {...props}></Icon>
