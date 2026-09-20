<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg00kur-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pg00kur-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:signal-full-remix" {...props}></Icon>
