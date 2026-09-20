<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7vqxtz8c.css';
import '../../css/j/jenqg7b4f.css';
import '../../css/o/ocwt-0blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q7vqxtz8c"/><path class="jenqg7b4f"/><path class="ocwt-0blw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:typewriter-flat" {...props}></Icon>
