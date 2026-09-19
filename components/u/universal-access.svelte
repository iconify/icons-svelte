<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct9n_cbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct9n_cbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:universal-access" {...props}></Icon>
