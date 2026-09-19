<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exjxxsb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exjxxsb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:service-instance-outlined" {...props}></Icon>
