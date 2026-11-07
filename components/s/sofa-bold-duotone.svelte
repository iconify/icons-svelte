<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp0cwnbgx.css';
import '../../css/y/y4fef2bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0cwnbgx"/><path class="y4fef2bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-bold-duotone" {...props}></Icon>
