<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5yhef5il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5yhef5il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-cards-outline" {...props}></Icon>
