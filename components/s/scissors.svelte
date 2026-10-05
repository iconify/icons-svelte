<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/o/o4d4euk0x.css';
import '../../css/c/cihnvjj0v.css';
import '../../css/c/cnj4nbc1z.css';
import '../../css/a/a5okeqbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="o4d4euk0x"/><path class="cihnvjj0v"/><path class="cnj4nbc1z"/><path class="a5okeqbkx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:scissors" {...props}></Icon>
