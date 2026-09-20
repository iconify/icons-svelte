<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4j4okbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4j4okbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:stethoscope-alt" {...props}></Icon>
