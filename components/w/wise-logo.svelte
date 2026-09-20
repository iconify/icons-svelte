<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vejl2qbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vejl2qbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wise-logo" {...props}></Icon>
