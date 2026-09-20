<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mir6zs6yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mir6zs6yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-escape-duotone" {...props}></Icon>
