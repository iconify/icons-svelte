<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vtgxl2bfl.css';
import '../../css/q/qm8lm0bxk.css';
import '../../css/r/r24s9n2mw.css';
import '../../css/g/gwohp6bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vtgxl2bfl"/><path class="qm8lm0bxk"/><path class="r24s9n2mw"/><path class="gwohp6bok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shrimp" {...props}></Icon>
