<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyq1n69xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyq1n69xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wheelchair-alt" {...props}></Icon>
