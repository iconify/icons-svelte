<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2gxi-bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2gxi-bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sensors" {...props}></Icon>
