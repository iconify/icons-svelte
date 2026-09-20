<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erdpm_zyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erdpm_zyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:spacing-large-24" {...props}></Icon>
