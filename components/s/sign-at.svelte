<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9d5ac6n.css';
import '../../css/b/bym2b9z7i.css';
import '../../css/m/m1vs99pas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="in9d5ac6n"><path class="bym2b9z7i"/><path class="m1vs99pas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:sign-at" {...props}></Icon>
