<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sokgaqver.css';
import '../../css/x/xnv-09bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sokgaqver"/><path class="xnv-09bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sign-in" {...props}></Icon>
