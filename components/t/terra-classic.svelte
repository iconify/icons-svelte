<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_f-8ebio.css';
import '../../css/d/dmqvb9ndz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_f-8ebio"/><path class="dmqvb9ndz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:terra-classic" {...props}></Icon>
