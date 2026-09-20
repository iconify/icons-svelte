<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqntpac5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cqntpac5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-single-neutral-male-remix" {...props}></Icon>
