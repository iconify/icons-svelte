<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frc14im-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frc14im-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sikh" {...props}></Icon>
