<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ondt29ssz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ondt29ssz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-uppercase" {...props}></Icon>
