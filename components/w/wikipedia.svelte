<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy_bfjbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy_bfjbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:wikipedia" {...props}></Icon>
