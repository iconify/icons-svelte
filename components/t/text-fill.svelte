<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubs7q-uca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubs7q-uca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:text-fill" {...props}></Icon>
