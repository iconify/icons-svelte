<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_alj1b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_alj1b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stackoverflow-logo-block" {...props}></Icon>
