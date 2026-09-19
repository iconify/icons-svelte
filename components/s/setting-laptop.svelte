<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kbesibb3g.css';
import '../../css/q/q0v-31bpj.css';
import '../../css/x/x2401pk9v.css';
import '../../css/g/g6li1jbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kbesibb3g"/><path class="q0v-31bpj"/><circle class="x2401pk9v"/><path class="g6li1jbuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:setting-laptop" {...props}></Icon>
