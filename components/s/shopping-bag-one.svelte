<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/casyzt9mq.css';
import '../../css/m/mq8edhbqg.css';
import '../../css/m/m-ojbcwmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="casyzt9mq"><rect class="mq8edhbqg"/><path class="m-ojbcwmy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shopping-bag-one" {...props}></Icon>
