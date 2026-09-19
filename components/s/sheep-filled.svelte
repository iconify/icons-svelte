<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c06djubit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c06djubit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sheep-filled" {...props}></Icon>
