<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqpor88k.css';
import '../../css/t/t-lei6bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqpor88k"/><path clip-rule="evenodd" class="t-lei6bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-bold" {...props}></Icon>
