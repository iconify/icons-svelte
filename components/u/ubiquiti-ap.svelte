<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3sfxpbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3sfxpbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-ap" {...props}></Icon>
