<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4bzr0bap.css';
import '../../css/z/z_bjwrbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4bzr0bap"/><path class="z_bjwrbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-check-20-bold" {...props}></Icon>
