<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p58xqpbbe.css';
import '../../css/k/klb8n8byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p58xqpbbe"/><circle class="klb8n8byj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:toggle" {...props}></Icon>
