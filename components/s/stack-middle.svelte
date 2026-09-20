<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nsemn25zi.css';
import '../../css/g/gtqbe8bko.css';
import '../../css/o/oza9rwbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nsemn25zi"/><path class="gtqbe8bko"/><path class="oza9rwbkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-middle" {...props}></Icon>
