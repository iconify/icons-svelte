<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7y7bpxwb.css';
import '../../css/u/u53qgwj4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7y7bpxwb"/><path class="u53qgwj4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:tree-fill" {...props}></Icon>
