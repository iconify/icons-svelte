<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd36bjb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dd36bjb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:supabase-dark" {...props}></Icon>
