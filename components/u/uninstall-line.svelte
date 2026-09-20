<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk9tf_p6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk9tf_p6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:uninstall-line" {...props}></Icon>
