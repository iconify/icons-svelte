<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj_h2eqbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_h2eqbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-info-solid" {...props}></Icon>
