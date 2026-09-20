<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1az0cgxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1az0cgxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yugabytedb-dark" {...props}></Icon>
