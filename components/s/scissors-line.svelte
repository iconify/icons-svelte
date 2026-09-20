<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eapga2xru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eapga2xru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-line" {...props}></Icon>
