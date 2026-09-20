<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5cqhtb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cqhtb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle-alert" {...props}></Icon>
