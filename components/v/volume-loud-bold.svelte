<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enqq2_4zj.css';
import '../../css/h/h12fbya6z.css';
import '../../css/k/kn7h3_b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enqq2_4zj"/><path class="h12fbya6z"/><path class="kn7h3_b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-loud-bold" {...props}></Icon>
