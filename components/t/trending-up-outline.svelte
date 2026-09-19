<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/ihqvv61nw.css';
import '../../css/e/evhc4ehqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="trending-up-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ihqvv61nw"/><path class="evhc4ehqx"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:trending-up-outline" {...props}></Icon>
