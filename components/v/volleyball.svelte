<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpm6fm9qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpm6fm9qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:volleyball" {...props}></Icon>
