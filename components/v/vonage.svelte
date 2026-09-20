<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctnit8fnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctnit8fnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vonage" {...props}></Icon>
