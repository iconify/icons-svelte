<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlixq-brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlixq-brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:screenshot-line" {...props}></Icon>
