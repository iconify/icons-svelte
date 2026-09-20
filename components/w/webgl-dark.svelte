<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdpfzv4oy.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/f/fzgukmboj.css';
import '../../css/g/gahp4sboa.css';
import '../../css/o/ofh7aqbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":500};
const content = `<path class="fdpfzv4oy"/><g class="n1mjunbsu"><path class="fzgukmboj"/><path class="gahp4sboa"/></g><path class="ofh7aqbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webgl-dark" {...props}></Icon>
