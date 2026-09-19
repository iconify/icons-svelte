<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cab465bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cab465bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:service-instance" {...props}></Icon>
