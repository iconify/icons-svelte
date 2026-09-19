<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-kbjab1h.css';
import '../../css/z/z7n6cqbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="z7n6cqbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:train" {...props}></Icon>
