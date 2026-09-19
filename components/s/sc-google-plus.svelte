<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu7shmw8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="cu7shmw8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-google-plus" {...props}></Icon>
