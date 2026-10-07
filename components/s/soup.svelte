<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qumtwzh_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qumtwzh_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:soup" {...props}></Icon>
