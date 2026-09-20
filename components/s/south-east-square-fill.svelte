<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ketapf1db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ketapf1db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-square-fill" {...props}></Icon>
