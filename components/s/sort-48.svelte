<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia3776b2n.css';
import '../../css/p/ptrhyzbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia3776b2n"/><path class="ptrhyzbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-48" {...props}></Icon>
