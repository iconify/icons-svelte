<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf8fnpfck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf8fnpfck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-big-right" {...props}></Icon>
