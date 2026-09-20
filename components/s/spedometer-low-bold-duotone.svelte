<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v31scrb0w.css';
import '../../css/s/sgn1aep-s.css';
import '../../css/u/ufg40xb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v31scrb0w"/><path class="sgn1aep-s"/><path class="ufg40xb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:spedometer-low-bold-duotone" {...props}></Icon>
