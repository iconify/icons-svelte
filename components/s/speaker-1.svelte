<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o1z2wccdo.css';
import '../../css/o/oq6o08blu.css';
import '../../css/k/kscen10md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="o1z2wccdo"/><path class="oq6o08blu"/><path class="kscen10md"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:speaker-1" {...props}></Icon>
