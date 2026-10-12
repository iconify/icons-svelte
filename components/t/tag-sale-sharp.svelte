<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v67nowbqx"/><circle class="bfo0bhbkc"/><path class="iwq0b8b5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tag-sale-sharp" {...props}></Icon>
<style>
:global(.bfo0bhbkc) {
  cx: 7px;
  cy: 12px;
  r: 1.1px;
}

:global(.iwq0b8b5y) {
  d: path("m15.28 7.79l.74.78l.28.29l.4-.01l1.08-.02l.4-.01l-.01.4l-.02 1.08l-.01.4l.29.28l.78.74l.29.28l-.29.28l-.78.74l-.29.28l.01.4l.02 1.08l.01.4l-.4-.01l-1.08-.02l-.4-.01l-.28.29l-.74.78l-.28.29l-.28-.29l-.74-.78l-.28-.29l-.4.01l-1.08.02l-.4.01l.01-.4l.02-1.08l.01-.4l-.29-.28l-.78-.74l-.29-.28l.29-.28l.78-.74l.29-.28l-.01-.4l-.02-1.08l-.01-.4l.4.01l1.08.02l.4.01l.28-.29l.74-.78l.28-.29zm-1.53 5.71l2.5-3");
}

:global(.v67nowbqx) {
  d: path("M8.66 5.75h12.59v12.5H8.66l-.886-.002l-.594-.658l-3.86-4.25L2.111 12l1.209-1.34l3.86-4.25l.594-.658z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
