<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjf41hbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjf41hbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-right-fill" {...props}></Icon>
