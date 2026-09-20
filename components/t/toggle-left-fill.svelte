<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hji4_vdzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hji4_vdzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-fill" {...props}></Icon>
