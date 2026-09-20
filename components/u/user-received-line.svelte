<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ucf8jbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ucf8jbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-received-line" {...props}></Icon>
