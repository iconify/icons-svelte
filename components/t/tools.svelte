<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbjjubn9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-1};
const content = `<path class="qbjjubn9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tools" {...props}></Icon>
