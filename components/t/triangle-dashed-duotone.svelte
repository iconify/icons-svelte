<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0e2h4bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z0e2h4bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-dashed-duotone" {...props}></Icon>
