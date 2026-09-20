<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqjc2cbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqjc2cbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-settings-fill" {...props}></Icon>
