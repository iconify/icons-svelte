<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tec5ddc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tec5ddc1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-out-line" {...props}></Icon>
