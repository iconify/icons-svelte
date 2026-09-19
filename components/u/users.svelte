<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jtck66bki.css';
import '../../css/t/t-u0yzblp.css';
import '../../css/w/wrzhokalt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jtck66bki"/><circle class="t-u0yzblp"/><path class="wrzhokalt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:users" {...props}></Icon>
