<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yitxoybmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yitxoybmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vanio" {...props}></Icon>
