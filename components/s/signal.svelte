<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ugdqbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ugdqbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:signal" {...props}></Icon>
