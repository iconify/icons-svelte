<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0s97_4wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0s97_4wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:service-outlined" {...props}></Icon>
