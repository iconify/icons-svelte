<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvvqs2vlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvvqs2vlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-edit" {...props}></Icon>
