<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3fi_0buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3fi_0buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:timer-reset-fill" {...props}></Icon>
