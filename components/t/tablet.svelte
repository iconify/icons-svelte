<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6b184-4c.css';
import '../../css/k/kv63i2wli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6b184-4c"/><path class="kv63i2wli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:tablet" {...props}></Icon>
