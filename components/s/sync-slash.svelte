<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9zs5b_ml.css';
import '../../css/y/ymqqe9y8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9zs5b_ml"/><path class="ymqqe9y8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sync-slash" {...props}></Icon>
