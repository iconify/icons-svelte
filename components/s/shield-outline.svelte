<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otpvh6y5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="shield-outline"><path class="(Stroke) 69 Vector otpvh6y5u" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:shield-outline" {...props}></Icon>
