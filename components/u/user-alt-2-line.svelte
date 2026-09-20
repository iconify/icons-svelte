<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxi0a1bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxi0a1bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-2-line" {...props}></Icon>
