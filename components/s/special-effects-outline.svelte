<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwfimpi9y.css';
import '../../css/z/z7wf0rbgy.css';
import '../../css/g/g4e643m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwfimpi9y"/><path class="z7wf0rbgy"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:special-effects-outline" {...props}></Icon>
