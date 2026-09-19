<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd2lkdd-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd2lkdd-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-bottom" {...props}></Icon>
