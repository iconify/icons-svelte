<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7x8w6hli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7x8w6hli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-circle-fill" {...props}></Icon>
