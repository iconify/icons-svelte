<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l08bx5bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l08bx5bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:science-outlined" {...props}></Icon>
